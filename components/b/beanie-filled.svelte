<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1b_yxnqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1b_yxnqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:beanie-filled" {...props}></Icon>
