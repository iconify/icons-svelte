<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0mvlgb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n0mvlgb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:negative" {...props}></Icon>
