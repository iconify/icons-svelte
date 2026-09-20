<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnfagub0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnfagub0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:calendar-question-mark-fill" {...props}></Icon>
