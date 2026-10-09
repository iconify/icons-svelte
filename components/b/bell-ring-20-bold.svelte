<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waxdi_b3y.css';
import '../../css/d/dqbca823b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="waxdi_b3y"/><path class="dqbca823b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-ring-20-bold" {...props}></Icon>
