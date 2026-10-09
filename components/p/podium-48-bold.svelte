<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr-eedcjf.css';
import '../../css/u/ua1y3_b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tr-eedcjf"/><path class="ua1y3_b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:podium-48-bold" {...props}></Icon>
