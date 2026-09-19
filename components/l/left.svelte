<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdpaesb5u.css';
import '../../css/r/rr_70iyii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="qdpaesb5u"/><path class="rr_70iyii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:left" {...props}></Icon>
