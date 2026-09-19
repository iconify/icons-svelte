<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zba5lxb9f.css';
import '../../css/e/e0u3nnbkg.css';
import '../../css/x/xbg8fwbvo.css';
import '../../css/j/jlao-fl0k.css';
import '../../css/r/r720bg59f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zba5lxb9f"/><path class="e0u3nnbkg"/><path class="xbg8fwbvo"/><path class="jlao-fl0k"/><path class="r720bg59f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:picture-twotone" {...props}></Icon>
