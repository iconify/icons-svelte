<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeuow5b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xeuow5b-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:keyhole" {...props}></Icon>
