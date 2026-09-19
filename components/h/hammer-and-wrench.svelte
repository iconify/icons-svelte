<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp2chbbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qp2chbbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:hammer-and-wrench" {...props}></Icon>
