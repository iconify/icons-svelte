<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sotbp4b5s.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="sotbp4b5s"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:purple-flag" {...props}></Icon>
