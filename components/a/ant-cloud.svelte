<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0qd5cgzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="t0qd5cgzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:ant-cloud" {...props}></Icon>
