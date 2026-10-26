<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz3_v7_xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kz3_v7_xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:lock-open" {...props}></Icon>
