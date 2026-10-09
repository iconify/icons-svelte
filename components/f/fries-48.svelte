<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1iximrex.css';
import '../../css/f/f7x3lpbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q1iximrex"/><path class="f7x3lpbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fries-48" {...props}></Icon>
