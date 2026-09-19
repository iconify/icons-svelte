<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxs5jcbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxs5jcbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-badge-check" {...props}></Icon>
