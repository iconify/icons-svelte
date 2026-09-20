<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbfrc-9ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="mbfrc-9ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:lock-small-solid" {...props}></Icon>
