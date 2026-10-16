<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5b5yobqi.css';
import '../../css/e/e7boe99qi.css';
import '../../css/o/os4jmsbas.css';
import '../../css/i/ihmii9b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x5b5yobqi"/><path class="e7boe99qi"/><path class="os4jmsbas"/><path class="ihmii9b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:parliament-48-bold" {...props}></Icon>
