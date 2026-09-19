<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh6xjib1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh6xjib1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-check-filled" {...props}></Icon>
