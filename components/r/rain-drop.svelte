<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b760q_svr.css';
import '../../css/k/k20av7rgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b760q_svr"/><path class="k20av7rgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rain-drop" {...props}></Icon>
