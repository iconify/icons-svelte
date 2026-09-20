<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myo-w__1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="myo-w__1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:flash-1-flat" {...props}></Icon>
