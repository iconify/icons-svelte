<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi62lyb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi62lyb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:chevron-right-circle" {...props}></Icon>
