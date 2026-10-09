<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udf9libzz.css';
import '../../css/a/a8yx3tbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="udf9libzz"/><path class="a8yx3tbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bread-48-bold" {...props}></Icon>
