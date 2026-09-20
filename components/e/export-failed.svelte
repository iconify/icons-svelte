<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7g0q9y_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="y7g0q9y_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:export-failed" {...props}></Icon>
