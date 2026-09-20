<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8ha5ackr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8ha5ackr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:calendar-fill" {...props}></Icon>
