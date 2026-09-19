<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szt_gcbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="szt_gcbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:radius-bottomleft-outline" {...props}></Icon>
