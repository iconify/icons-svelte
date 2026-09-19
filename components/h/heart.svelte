<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe24ebbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oe24ebbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:heart" {...props}></Icon>
