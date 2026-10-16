<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xszdr5bbz.css';
import '../../css/k/klmj08ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xszdr5bbz"/><path class="klmj08ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:control-rod-48-bold" {...props}></Icon>
