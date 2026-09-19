<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz5s9uirz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wz5s9uirz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:joints-outline" {...props}></Icon>
