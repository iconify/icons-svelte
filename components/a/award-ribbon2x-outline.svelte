<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj5b0nhsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uj5b0nhsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:award-ribbon2x-outline" {...props}></Icon>
