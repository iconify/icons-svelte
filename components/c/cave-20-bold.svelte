<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw792fgla.css';
import '../../css/d/dq1tynbis.css';
import '../../css/a/ale17-bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fw792fgla"/><path class="dq1tynbis"/><path class="ale17-bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cave-20-bold" {...props}></Icon>
