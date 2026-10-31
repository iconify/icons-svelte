<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5nf1ub8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5nf1ub8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-right-round" {...props}></Icon>
