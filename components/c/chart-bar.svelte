<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqfo8ifwt.css';
import '../../css/k/kc03hjs4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqfo8ifwt"/><path class="kc03hjs4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:chart-bar" {...props}></Icon>
