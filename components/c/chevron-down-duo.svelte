<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ompeivchl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ompeivchl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevron-down-duo" {...props}></Icon>
