<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt6q08rtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jt6q08rtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:arrow-down-outlined" {...props}></Icon>
