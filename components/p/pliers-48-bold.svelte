<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0hsllbzz.css';
import '../../css/h/hsyyodqzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x0hsllbzz"/><path class="hsyyodqzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pliers-48-bold" {...props}></Icon>
