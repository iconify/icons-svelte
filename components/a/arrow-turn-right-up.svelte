<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx946b01g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hx946b01g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-turn-right-up" {...props}></Icon>
