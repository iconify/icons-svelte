<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib9hyvbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":632};
const content = `<path class="ib9hyvbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:folder" {...props}></Icon>
