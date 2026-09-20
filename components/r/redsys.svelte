<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgkvc_bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgkvc_bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:redsys" {...props}></Icon>
