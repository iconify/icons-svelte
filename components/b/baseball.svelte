<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv2q9dqxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nv2q9dqxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:baseball" {...props}></Icon>
