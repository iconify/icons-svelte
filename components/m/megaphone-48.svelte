<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gofrhbcai.css';
import '../../css/t/tpe_wnyve.css';
import '../../css/k/kr1msob9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gofrhbcai"/><path class="tpe_wnyve"/><path class="kr1msob9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:megaphone-48" {...props}></Icon>
