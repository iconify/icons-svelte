<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muu8gqd7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muu8gqd7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar" {...props}></Icon>
