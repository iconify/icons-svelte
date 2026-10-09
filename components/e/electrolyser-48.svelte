<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk8dzgglt.css';
import '../../css/e/eg02k6bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lk8dzgglt"/><path class="eg02k6bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electrolyser-48" {...props}></Icon>
