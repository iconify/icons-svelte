<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f85yefe1j.css';
import '../../css/j/jso3jy2en.css';
import '../../css/r/r45tgcbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f85yefe1j"/><path class="jso3jy2en"/><path class="r45tgcbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-excel-twotone" {...props}></Icon>
