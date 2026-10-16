<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9ka3cc1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e9ka3cc1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:infrared-panel-48-bold" {...props}></Icon>
