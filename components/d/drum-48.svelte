<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbk4vsmtj.css';
import '../../css/w/ww_xydb2s.css';
import '../../css/e/ejdsdgbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qbk4vsmtj"/><path class="ww_xydb2s"/><path class="ejdsdgbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drum-48" {...props}></Icon>
