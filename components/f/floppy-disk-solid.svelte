<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcvggebaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jcvggebaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:floppy-disk-solid" {...props}></Icon>
