<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etuvs-83s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="etuvs-83s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-button-to-top-arrow-up-line-to-top" {...props}></Icon>
