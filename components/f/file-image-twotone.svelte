<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9j99ekyh.css';
import '../../css/j/jso3jy2en.css';
import '../../css/k/kbsh_4bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s9j99ekyh"/><path class="jso3jy2en"/><path class="kbsh_4bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-image-twotone" {...props}></Icon>
