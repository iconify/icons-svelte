<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maj5unbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="maj5unbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:calendar-event" {...props}></Icon>
