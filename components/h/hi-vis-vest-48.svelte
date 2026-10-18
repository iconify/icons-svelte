<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkegzz3bi.css';
import '../../css/h/h07j5abjx.css';
import '../../css/w/ws21njb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hkegzz3bi"/><path class="h07j5abjx"/><path class="ws21njb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hi-vis-vest-48" {...props}></Icon>
