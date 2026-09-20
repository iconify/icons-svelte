<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh821mhzp.css';
import '../../css/k/kidrbbcux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zh821mhzp"/><path class="kidrbbcux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:edit" {...props}></Icon>
