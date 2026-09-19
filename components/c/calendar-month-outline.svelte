<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnqm6cc8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnqm6cc8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:calendar-month-outline" {...props}></Icon>
