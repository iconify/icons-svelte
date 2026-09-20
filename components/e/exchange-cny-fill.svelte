<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h36zf1bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h36zf1bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:exchange-cny-fill" {...props}></Icon>
