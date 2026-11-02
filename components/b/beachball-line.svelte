<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxzv38bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxzv38bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:beachball-line" {...props}></Icon>
