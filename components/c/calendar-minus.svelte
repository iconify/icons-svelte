<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voswg_4lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voswg_4lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-minus" {...props}></Icon>
