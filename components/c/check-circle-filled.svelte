<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6dw91kyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k6dw91kyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:check-circle-filled" {...props}></Icon>
