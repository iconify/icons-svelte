<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1tx5ebwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w1tx5ebwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:mouse-fill" {...props}></Icon>
