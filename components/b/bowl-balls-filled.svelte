<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so6vp6w1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so6vp6w1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bowl-balls-filled" {...props}></Icon>
