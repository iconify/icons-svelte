<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufuq57bcj.css';
import '../../css/t/t8y2ocbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufuq57bcj"/><path class="t8y2ocbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:calendar-date" {...props}></Icon>
