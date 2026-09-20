<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h80xxeoac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h80xxeoac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:plus-line" {...props}></Icon>
