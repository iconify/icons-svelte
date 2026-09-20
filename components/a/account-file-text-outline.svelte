<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bot5o0b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bot5o0b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-file-text-outline" {...props}></Icon>
