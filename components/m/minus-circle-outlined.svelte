<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zurui3ban.css';
import '../../css/y/yv_brepse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zurui3ban"/><path class="yv_brepse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:minus-circle-outlined" {...props}></Icon>
