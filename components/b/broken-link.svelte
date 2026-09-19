<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq_0qxfmx.css';
import '../../css/y/yu51uzbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zq_0qxfmx"/><path class="yu51uzbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:broken-link" {...props}></Icon>
