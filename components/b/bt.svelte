<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0cdnpy2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0cdnpy2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bt" {...props}></Icon>
