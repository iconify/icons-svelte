<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr7h2fb6d.css';
import '../../css/s/svhavybtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lr7h2fb6d"/><path class="svhavybtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dice-1-48" {...props}></Icon>
