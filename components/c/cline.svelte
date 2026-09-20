<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbzbq6bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbzbq6bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cline" {...props}></Icon>
