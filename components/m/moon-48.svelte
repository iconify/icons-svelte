<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_v4z1q3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a_v4z1q3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-48" {...props}></Icon>
