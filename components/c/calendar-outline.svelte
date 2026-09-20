<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2miiia8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h2miiia8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:calendar-outline" {...props}></Icon>
