<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq6x3_7zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq6x3_7zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-plus" {...props}></Icon>
