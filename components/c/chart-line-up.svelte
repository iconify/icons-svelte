<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shgejf8-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shgejf8-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chart-line-up" {...props}></Icon>
