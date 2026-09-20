<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0q-oiapk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w0q-oiapk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:lightbulb-solid" {...props}></Icon>
