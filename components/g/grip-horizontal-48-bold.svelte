<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nox51db9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nox51db9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grip-horizontal-48-bold" {...props}></Icon>
