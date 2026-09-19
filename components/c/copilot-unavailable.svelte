<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo8q-3hhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mo8q-3hhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:copilot-unavailable" {...props}></Icon>
