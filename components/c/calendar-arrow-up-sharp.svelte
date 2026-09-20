<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5-9mdbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5-9mdbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-arrow-up-sharp" {...props}></Icon>
