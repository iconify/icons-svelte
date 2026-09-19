<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6v0htbfx.css';
import '../../css/j/jso3jy2en.css';
import '../../css/e/eca5gmkyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d6v0htbfx"/><path class="jso3jy2en"/><path class="eca5gmkyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-markdown-twotone" {...props}></Icon>
