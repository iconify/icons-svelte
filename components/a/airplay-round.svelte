<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqaj_ob-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqaj_ob-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:airplay-round" {...props}></Icon>
