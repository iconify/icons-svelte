<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-scmdk6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-scmdk6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-add" {...props}></Icon>
