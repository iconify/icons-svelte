<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxx19tb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lxx19tb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:braille-blind-solid" {...props}></Icon>
