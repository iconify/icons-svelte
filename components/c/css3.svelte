<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yopy-3xrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="yopy-3xrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:css3" {...props}></Icon>
