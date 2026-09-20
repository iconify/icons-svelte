<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1fsbgbhg.css';
import '../../css/e/ezh8crbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1fsbgbhg"/><path class="ezh8crbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:calendar-plus" {...props}></Icon>
