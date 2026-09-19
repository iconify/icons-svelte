<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcb2srqrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zcb2srqrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:dailymotion" {...props}></Icon>
