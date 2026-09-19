<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzqqceb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzqqceb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calendar-04" {...props}></Icon>
