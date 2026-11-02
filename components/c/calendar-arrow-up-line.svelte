<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byx32bbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byx32bbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-arrow-up-line" {...props}></Icon>
