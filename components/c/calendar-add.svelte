<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lekob1bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lekob1bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:calendar-add" {...props}></Icon>
