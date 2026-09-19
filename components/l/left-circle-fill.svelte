<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a929an8zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a929an8zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:left-circle-fill" {...props}></Icon>
