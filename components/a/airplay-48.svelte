<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agimoob8o.css';
import '../../css/m/m8c88eb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="agimoob8o"/><path class="m8c88eb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:airplay-48" {...props}></Icon>
