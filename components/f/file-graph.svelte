<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftowa7x3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftowa7x3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-graph" {...props}></Icon>
