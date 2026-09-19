<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezf1yo0lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezf1yo0lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calendar-02" {...props}></Icon>
