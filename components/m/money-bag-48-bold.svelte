<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctvev1biw.css';
import '../../css/q/qis7irbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ctvev1biw"/><path class="qis7irbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:money-bag-48-bold" {...props}></Icon>
