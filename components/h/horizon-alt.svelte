<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7y00378n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="c7y00378n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:horizon-alt" {...props}></Icon>
