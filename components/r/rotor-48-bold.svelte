<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbfpednqz.css';
import '../../css/z/zl1nmrb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qbfpednqz"/><path class="zl1nmrb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rotor-48-bold" {...props}></Icon>
