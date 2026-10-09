<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lymkpobns.css';
import '../../css/x/xfeis42ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lymkpobns"/><path class="xfeis42ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:prism-48" {...props}></Icon>
