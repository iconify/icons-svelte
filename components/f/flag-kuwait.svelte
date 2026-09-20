<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8cxt48ie.css';
import '../../css/r/r73utib8z.css';
import '../../css/d/duy2v2t-d.css';
import '../../css/q/qvywvgb0u.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="e8cxt48ie"/><path class="r73utib8z"/><path class="duy2v2t-d"/><path class="qvywvgb0u"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-kuwait" {...props}></Icon>
