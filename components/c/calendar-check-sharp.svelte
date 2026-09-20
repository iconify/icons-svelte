<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6gn0sbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6gn0sbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-check-sharp" {...props}></Icon>
