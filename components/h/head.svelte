<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2dotabzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h2dotabzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:head" {...props}></Icon>
