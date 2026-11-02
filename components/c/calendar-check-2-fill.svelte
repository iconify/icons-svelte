<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpciqvudz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpciqvudz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-check-2-fill" {...props}></Icon>
