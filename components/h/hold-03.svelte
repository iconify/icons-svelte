<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzp351bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzp351bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hold-03" {...props}></Icon>
