<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpl6ieb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpl6ieb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-1-filled" {...props}></Icon>
