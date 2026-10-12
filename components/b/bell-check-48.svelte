<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msmn8bbfm.css';
import '../../css/x/xgyzx9bhy.css';
import '../../css/z/z4sj3ixdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="msmn8bbfm"/><path class="xgyzx9bhy"/><path class="z4sj3ixdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-check-48" {...props}></Icon>
