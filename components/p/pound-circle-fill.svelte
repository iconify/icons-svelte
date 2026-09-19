<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob82bpbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ob82bpbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:pound-circle-fill" {...props}></Icon>
