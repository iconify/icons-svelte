<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrbs79i2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mrbs79i2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:controller-wireless-solid" {...props}></Icon>
