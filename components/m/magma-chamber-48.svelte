<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5yplhb0m.css';
import '../../css/y/y49f7hyag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e5yplhb0m"/><path class="y49f7hyag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:magma-chamber-48" {...props}></Icon>
