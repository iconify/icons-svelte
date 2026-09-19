<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyz5hkbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qyz5hkbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:deep-seek-filled" {...props}></Icon>
