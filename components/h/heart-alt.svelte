<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/capx64hcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="capx64hcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:heart-alt" {...props}></Icon>
