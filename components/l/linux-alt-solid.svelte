<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd-74fbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kd-74fbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:linux-alt-solid" {...props}></Icon>
