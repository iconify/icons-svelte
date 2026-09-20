<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcu-63jaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xcu-63jaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:edit-document-filled" {...props}></Icon>
