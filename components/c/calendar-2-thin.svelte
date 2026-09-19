<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaws_22cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kaws_22cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calendar-2-thin" {...props}></Icon>
