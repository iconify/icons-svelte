<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkp57tl3g.css';
import '../../css/d/dhq72bbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pkp57tl3g"/><path class="dhq72bbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:expansion-vessel-20-bold" {...props}></Icon>
