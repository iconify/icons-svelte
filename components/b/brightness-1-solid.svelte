<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wie4h70nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wie4h70nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:brightness-1-solid" {...props}></Icon>
