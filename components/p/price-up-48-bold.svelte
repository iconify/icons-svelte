<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcp6u-oop.css';
import '../../css/x/xgx2z7ryy.css';
import '../../css/o/o4v1t0brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qcp6u-oop"/><path class="xgx2z7ryy"/><path class="o4v1t0brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:price-up-48-bold" {...props}></Icon>
