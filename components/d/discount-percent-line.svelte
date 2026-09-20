<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkof6pkkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkof6pkkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:discount-percent-line" {...props}></Icon>
