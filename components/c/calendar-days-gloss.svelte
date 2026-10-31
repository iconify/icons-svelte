<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etaokrw9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etaokrw9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-days-gloss" {...props}></Icon>
