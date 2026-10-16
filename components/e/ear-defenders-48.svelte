<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6ezflbgv.css';
import '../../css/r/rx83a-b1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i6ezflbgv"/><path class="rx83a-b1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ear-defenders-48" {...props}></Icon>
