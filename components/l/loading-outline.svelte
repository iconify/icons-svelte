<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d__xc-bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d__xc-bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:loading-outline" {...props}></Icon>
