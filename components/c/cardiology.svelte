<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxk146b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zxk146b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cardiology" {...props}></Icon>
