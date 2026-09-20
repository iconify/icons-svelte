<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brzibym8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brzibym8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:calendar-2" {...props}></Icon>
