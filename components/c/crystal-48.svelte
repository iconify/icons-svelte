<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7qd3ubqx.css';
import '../../css/j/j4kecacgy.css';
import '../../css/z/ztnyhokgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m7qd3ubqx"/><path class="j4kecacgy"/><path class="ztnyhokgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crystal-48" {...props}></Icon>
