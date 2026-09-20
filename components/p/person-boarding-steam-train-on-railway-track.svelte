<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnawj1_sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wnawj1_sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-boarding-steam-train-on-railway-track" {...props}></Icon>
