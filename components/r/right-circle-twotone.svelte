<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9xelbb4d.css';
import '../../css/y/yv_brepse.css';
import '../../css/l/lpz0abbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k9xelbb4d"/><path class="yv_brepse"/><path class="lpz0abbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:right-circle-twotone" {...props}></Icon>
