<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4kzwwbha.css';
import '../../css/n/n5_c-mepp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e4kzwwbha"/><path class="n5_c-mepp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cheese-48-bold" {...props}></Icon>
