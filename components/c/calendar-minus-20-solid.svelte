<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9y95dbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="t9y95dbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-minus-20-solid" {...props}></Icon>
