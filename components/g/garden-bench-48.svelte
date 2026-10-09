<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyrr7ohpi.css';
import '../../css/v/v_nw6fb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fyrr7ohpi"/><path class="v_nw6fb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:garden-bench-48" {...props}></Icon>
