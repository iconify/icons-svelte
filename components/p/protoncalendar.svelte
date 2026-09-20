<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8q52ackl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8q52ackl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:protoncalendar" {...props}></Icon>
