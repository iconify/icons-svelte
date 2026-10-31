<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j57k96fxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j57k96fxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-edit-corner-round" {...props}></Icon>
