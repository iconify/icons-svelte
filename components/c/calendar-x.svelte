<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ornszl9rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ornszl9rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:calendar-x" {...props}></Icon>
