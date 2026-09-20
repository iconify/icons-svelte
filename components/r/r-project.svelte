<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvpsqq7ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qvpsqq7ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:r-project" {...props}></Icon>
