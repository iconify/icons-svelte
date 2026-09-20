<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyf_7abpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyf_7abpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:calendar-month" {...props}></Icon>
