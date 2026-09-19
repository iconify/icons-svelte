<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1i7d-1da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x1i7d-1da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:message-fill" {...props}></Icon>
