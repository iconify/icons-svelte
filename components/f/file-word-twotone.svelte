<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9wvyeb-k.css';
import '../../css/j/jso3jy2en.css';
import '../../css/c/czglw1bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w9wvyeb-k"/><path class="jso3jy2en"/><path class="czglw1bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-word-twotone" {...props}></Icon>
