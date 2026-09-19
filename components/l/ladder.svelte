<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz4tvtbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pz4tvtbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:ladder" {...props}></Icon>
