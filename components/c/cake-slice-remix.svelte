<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzo9n2i8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mzo9n2i8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cake-slice-remix" {...props}></Icon>
