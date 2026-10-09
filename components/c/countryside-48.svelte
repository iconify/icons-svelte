<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_c1rlbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q_c1rlbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:countryside-48" {...props}></Icon>
