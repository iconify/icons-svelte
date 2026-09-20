<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6v4gqm0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6v4gqm0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:calendar-cog" {...props}></Icon>
