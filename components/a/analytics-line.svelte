<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt9l-fdny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt9l-fdny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:analytics-line" {...props}></Icon>
