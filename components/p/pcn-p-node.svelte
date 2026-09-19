<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0el-pkyw.css';
import '../../css/j/j8yh1x58g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v0el-pkyw"/><path class="j8yh1x58g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pcn-p-node" {...props}></Icon>
