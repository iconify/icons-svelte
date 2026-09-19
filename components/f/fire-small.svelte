<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_wb409zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="u_wb409zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:fire-small" {...props}></Icon>
