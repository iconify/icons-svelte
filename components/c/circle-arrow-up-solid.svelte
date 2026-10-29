<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9r2uab5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9r2uab5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-arrow-up-solid" {...props}></Icon>
