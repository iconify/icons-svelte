<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp6js4-lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp6js4-lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:calendar-minus" {...props}></Icon>
