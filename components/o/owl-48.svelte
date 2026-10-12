<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnv8bn3zi.css';
import '../../css/x/xqa9wgbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hnv8bn3zi"/><path class="xqa9wgbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:owl-48" {...props}></Icon>
