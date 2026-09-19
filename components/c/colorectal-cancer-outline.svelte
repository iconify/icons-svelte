<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9y5-zbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s9y5-zbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:colorectal-cancer-outline" {...props}></Icon>
