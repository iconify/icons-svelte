<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv25jcc7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv25jcc7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-plus-corner-fill-round" {...props}></Icon>
