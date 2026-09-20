<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-7so2bbd.css';
import '../../css/n/nna3xilgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m-7so2bbd"/><path class="nna3xilgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:car-repair-15" {...props}></Icon>
