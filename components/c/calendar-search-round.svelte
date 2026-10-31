<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocrm3nc-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocrm3nc-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-search-round" {...props}></Icon>
