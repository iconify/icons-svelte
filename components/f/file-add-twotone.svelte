<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7mk-dp-h.css';
import '../../css/j/jso3jy2en.css';
import '../../css/n/n5rxf3buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="t7mk-dp-h"/><path class="jso3jy2en"/><path class="n5rxf3buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-add-twotone" {...props}></Icon>
