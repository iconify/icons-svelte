<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf7xaq13d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="mf7xaq13d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:mars-stroke-h" {...props}></Icon>
