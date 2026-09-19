<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hszka1bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hszka1bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:head-outline" {...props}></Icon>
