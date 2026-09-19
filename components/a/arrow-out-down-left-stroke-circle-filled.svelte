<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yerncn7yx.css';
import '../../css/i/i-33urxjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yerncn7yx"/><path class="i-33urxjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-left-stroke-circle-filled" {...props}></Icon>
