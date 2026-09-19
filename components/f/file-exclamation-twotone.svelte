<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk-nafbcd.css';
import '../../css/j/jso3jy2en.css';
import '../../css/k/kpy2_do4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dk-nafbcd"/><path class="jso3jy2en"/><path class="kpy2_do4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-exclamation-twotone" {...props}></Icon>
