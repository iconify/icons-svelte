<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf2pff15t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hf2pff15t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:application-add-solid" {...props}></Icon>
