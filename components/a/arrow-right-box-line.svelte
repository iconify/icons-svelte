<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmhf-k_uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmhf-k_uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-box-line" {...props}></Icon>
