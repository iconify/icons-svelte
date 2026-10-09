<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzpt0u8pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qzpt0u8pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clouds-48-bold" {...props}></Icon>
