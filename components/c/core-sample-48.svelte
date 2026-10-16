<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5g_98bjs.css';
import '../../css/i/ibk4nlb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s5g_98bjs"/><path class="ibk4nlb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:core-sample-48" {...props}></Icon>
