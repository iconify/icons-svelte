<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnizhvbij.css';
import '../../css/c/cbbk25b7d.css';
import '../../css/k/kwxtwsb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nnizhvbij"/><path class="cbbk25b7d"/><path class="kwxtwsb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blade-transport-48" {...props}></Icon>
