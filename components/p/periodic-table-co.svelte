<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7jf82b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7jf82b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:periodic-table-co" {...props}></Icon>
