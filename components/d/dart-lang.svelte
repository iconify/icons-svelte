<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muoe_lbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="muoe_lbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:dart-lang" {...props}></Icon>
