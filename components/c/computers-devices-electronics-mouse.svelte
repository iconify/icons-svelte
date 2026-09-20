<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5n7r2czb.css';
import '../../css/m/muo8ifbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k5n7r2czb"/><path class="muo8ifbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-mouse" {...props}></Icon>
