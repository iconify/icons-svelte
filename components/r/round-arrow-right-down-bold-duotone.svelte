<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c77vne7ui.css';
import '../../css/a/aawp35beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c77vne7ui"/><path class="aawp35beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-arrow-right-down-bold-duotone" {...props}></Icon>
