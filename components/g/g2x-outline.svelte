<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-amvrbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p-amvrbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:g2x-outline" {...props}></Icon>
