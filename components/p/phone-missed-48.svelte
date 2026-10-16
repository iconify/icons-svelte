<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9xwe29zq.css';
import '../../css/l/lyuckzd_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b9xwe29zq"/><path class="lyuckzd_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-missed-48" {...props}></Icon>
