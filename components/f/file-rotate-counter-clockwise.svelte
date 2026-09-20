<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwcb9nbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwcb9nbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-rotate-counter-clockwise" {...props}></Icon>
