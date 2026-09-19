<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_inv4bnz.css';
import '../../css/x/xej_6xgaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x_inv4bnz"/><path class="xej_6xgaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:npm" {...props}></Icon>
