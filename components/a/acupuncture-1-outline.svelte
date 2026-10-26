<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyctcdb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xyctcdb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:acupuncture-1-outline" {...props}></Icon>
