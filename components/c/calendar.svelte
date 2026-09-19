<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9g-qxb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9g-qxb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:calendar" {...props}></Icon>
