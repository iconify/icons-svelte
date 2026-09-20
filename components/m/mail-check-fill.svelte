<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v16u2yk6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v16u2yk6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-check-fill" {...props}></Icon>
