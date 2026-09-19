<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrscrbb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zrscrbb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:body" {...props}></Icon>
