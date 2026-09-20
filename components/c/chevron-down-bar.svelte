<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whi-88vin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="whi-88vin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chevron-down-bar" {...props}></Icon>
