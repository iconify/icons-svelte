<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryifenczr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ryifenczr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:radiology" {...props}></Icon>
