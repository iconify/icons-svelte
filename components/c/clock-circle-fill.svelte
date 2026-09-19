<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6vfd5a9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u6vfd5a9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:clock-circle-fill" {...props}></Icon>
