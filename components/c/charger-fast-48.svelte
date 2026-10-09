<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5ebr9bjc.css';
import '../../css/n/ng0ti4b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p5ebr9bjc"/><path class="ng0ti4b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-fast-48" {...props}></Icon>
