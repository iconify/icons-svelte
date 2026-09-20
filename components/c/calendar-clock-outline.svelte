<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_4tbqbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_4tbqbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-clock-outline" {...props}></Icon>
