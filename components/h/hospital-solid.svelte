<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgj6zf-os.css';
import '../../css/d/dif-cubim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="sgj6zf-os"/><path class="dif-cubim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:hospital-solid" {...props}></Icon>
