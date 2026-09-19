<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9o2spbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f9o2spbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:02x-outline" {...props}></Icon>
