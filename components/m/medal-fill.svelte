<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_bot4blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_bot4blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:medal-fill" {...props}></Icon>
