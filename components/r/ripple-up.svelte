<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob7yn8b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob7yn8b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ripple-up" {...props}></Icon>
