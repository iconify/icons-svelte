<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxhj9lv9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zxhj9lv9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-line2x-outline" {...props}></Icon>
