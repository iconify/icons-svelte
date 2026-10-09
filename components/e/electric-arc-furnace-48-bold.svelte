<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqszs5bfa.css';
import '../../css/e/et3b916ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cqszs5bfa"/><path class="et3b916ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-arc-furnace-48-bold" {...props}></Icon>
