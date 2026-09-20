<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuehshduq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yuehshduq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hammer-with-nail" {...props}></Icon>
