<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-f-pn66e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-f-pn66e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:paper-add" {...props}></Icon>
