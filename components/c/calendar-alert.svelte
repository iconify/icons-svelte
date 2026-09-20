<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nswil6bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nswil6bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-alert" {...props}></Icon>
