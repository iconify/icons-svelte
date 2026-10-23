<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxw52nabo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxw52nabo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-cog" {...props}></Icon>
