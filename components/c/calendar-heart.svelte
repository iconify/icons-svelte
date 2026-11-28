<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6fr_n7rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6fr_n7rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:calendar-heart" {...props}></Icon>
