<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sev_i2bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sev_i2bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-up-48" {...props}></Icon>
