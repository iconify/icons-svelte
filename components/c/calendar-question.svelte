<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukk04mbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukk04mbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:calendar-question" {...props}></Icon>
