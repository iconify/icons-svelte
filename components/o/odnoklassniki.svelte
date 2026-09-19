<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b48oo7bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":24};
const content = `<path class="b48oo7bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:odnoklassniki" {...props}></Icon>
