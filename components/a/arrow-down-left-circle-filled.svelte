<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1f0oo91k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1f0oo91k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-left-circle-filled" {...props}></Icon>
