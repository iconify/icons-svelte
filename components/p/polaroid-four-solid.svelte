<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu_xfvj-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tu_xfvj-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:polaroid-four-solid" {...props}></Icon>
