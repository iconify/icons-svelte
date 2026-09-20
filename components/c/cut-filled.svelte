<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2jgm9-lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="e2jgm9-lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cut-filled" {...props}></Icon>
