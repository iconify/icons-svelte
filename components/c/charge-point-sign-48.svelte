<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbwxlclgf.css';
import '../../css/u/u5hq78bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lbwxlclgf"/><path class="u5hq78bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charge-point-sign-48" {...props}></Icon>
