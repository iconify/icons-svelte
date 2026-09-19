<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0mko4zde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z0mko4zde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:home-alt" {...props}></Icon>
