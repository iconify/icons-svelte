<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1d2wgbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c1d2wgbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:candy-cane-solid" {...props}></Icon>
