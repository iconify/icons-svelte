<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zldktgsnj.css';
import '../../css/o/o2cku2b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zldktgsnj"/><path class="o2cku2b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:procurement-48" {...props}></Icon>
