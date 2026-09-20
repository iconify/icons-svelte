<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-mcxxb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="y-mcxxb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:entertainment-ticket-hobby-ticket-event-entertainment-stub-theater" {...props}></Icon>
