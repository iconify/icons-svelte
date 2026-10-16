<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4r0n-daa.css';
import '../../css/d/dzy_-taoh.css';
import '../../css/k/ktd6x_fpp.css';
import '../../css/x/x-e56pbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c4r0n-daa"/><path class="dzy_-taoh"/><path class="ktd6x_fpp"/><path class="x-e56pbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mosque-20-bold" {...props}></Icon>
