<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egi8qzduf.css';
import '../../css/t/tly4pwr5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="egi8qzduf"/><path class="tly4pwr5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-tub-48" {...props}></Icon>
