<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed2wdwblh.css';
import '../../css/y/y2dquhbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ed2wdwblh"/><path class="y2dquhbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rotate-cw-48-bold" {...props}></Icon>
