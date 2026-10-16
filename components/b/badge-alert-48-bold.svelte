<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si1030bhs.css';
import '../../css/e/e0fdkfvpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="si1030bhs"/><path class="e0fdkfvpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badge-alert-48-bold" {...props}></Icon>
