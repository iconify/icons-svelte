<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it7-fkk5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it7-fkk5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:line-chart-square-filled" {...props}></Icon>
