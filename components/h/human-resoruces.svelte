<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6_ehmbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e6_ehmbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:human-resoruces" {...props}></Icon>
