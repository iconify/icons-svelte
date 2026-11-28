<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru_7_3len.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru_7_3len"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:air-conditioner-x" {...props}></Icon>
