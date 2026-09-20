<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx40fmwto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-4};
const content = `<path class="jx40fmwto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:rec" {...props}></Icon>
