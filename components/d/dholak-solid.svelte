<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unwd-kbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unwd-kbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dholak-solid" {...props}></Icon>
