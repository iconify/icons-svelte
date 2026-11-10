<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py1c9c1oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="py1c9c1oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-exclamation-20-solid" {...props}></Icon>
