<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-bnw_0yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q-bnw_0yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:pass-filled" {...props}></Icon>
