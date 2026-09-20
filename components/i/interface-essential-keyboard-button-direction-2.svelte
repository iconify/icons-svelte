<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of6y9uq3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="of6y9uq3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-keyboard-button-direction-2" {...props}></Icon>
