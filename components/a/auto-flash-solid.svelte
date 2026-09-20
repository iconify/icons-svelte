<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feurjdvol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="feurjdvol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:auto-flash-solid" {...props}></Icon>
