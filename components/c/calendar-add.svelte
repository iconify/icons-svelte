<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj91innbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj91innbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calendar-add" {...props}></Icon>
