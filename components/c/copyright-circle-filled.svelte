<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_v3zxy6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x_v3zxy6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:copyright-circle-filled" {...props}></Icon>
