<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbb2-5bwt.css';
import '../../css/o/o855tz_5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cbb2-5bwt"/><path class="o855tz_5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:rotate-left-outlined" {...props}></Icon>
