<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otsew2bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="otsew2bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-power-1-solid" {...props}></Icon>
