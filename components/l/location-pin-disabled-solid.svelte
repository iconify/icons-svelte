<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbs3igb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fbs3igb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:location-pin-disabled-solid" {...props}></Icon>
