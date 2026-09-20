<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u80r11ida.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u80r11ida"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:radio-solid" {...props}></Icon>
