<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqt1zbbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dqt1zbbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:circular-pill" {...props}></Icon>
