<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih9a8_b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih9a8_b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-text-arrow-down" {...props}></Icon>
