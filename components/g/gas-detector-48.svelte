<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvn-b1bgm.css';
import '../../css/x/xszy37jky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jvn-b1bgm"/><path class="xszy37jky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-detector-48" {...props}></Icon>
