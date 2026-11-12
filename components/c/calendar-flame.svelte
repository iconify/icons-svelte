<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnpi_abmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnpi_abmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:calendar-flame" {...props}></Icon>
