<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psemm7bpq.css';
import '../../css/y/yeivt_bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="psemm7bpq"/><path class="yeivt_bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hash-48" {...props}></Icon>
