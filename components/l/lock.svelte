<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhk_qq-5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="qhk_qq-5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:lock" {...props}></Icon>
