<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqnf0qmsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqnf0qmsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-days" {...props}></Icon>
