<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngy-kfbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngy-kfbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:calendar-alt" {...props}></Icon>
