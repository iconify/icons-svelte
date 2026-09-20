<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj5e91bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oj5e91bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-expand-vertical" {...props}></Icon>
