<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm3xmebmn.css';
import '../../css/a/aglz3sohk.css';
import '../../css/z/zjcvkggsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qm3xmebmn"/><path class="aglz3sohk"/><path class="zjcvkggsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:property-safety-twotone" {...props}></Icon>
