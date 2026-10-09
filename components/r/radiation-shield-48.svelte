<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlsrljbwz.css';
import '../../css/c/cbs5z2bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rlsrljbwz"/><path class="cbs5z2bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:radiation-shield-48" {...props}></Icon>
