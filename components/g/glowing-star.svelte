<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exo_ym68c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="exo_ym68c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:glowing-star" {...props}></Icon>
