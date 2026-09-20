<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5wwqfbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5wwqfbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-up-box-line" {...props}></Icon>
