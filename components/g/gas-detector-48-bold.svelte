<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmty_lb2n.css';
import '../../css/b/b_dryruwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kmty_lb2n"/><path class="b_dryruwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-detector-48-bold" {...props}></Icon>
