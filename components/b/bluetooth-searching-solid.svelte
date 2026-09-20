<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8d_vgbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m8d_vgbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bluetooth-searching-solid" {...props}></Icon>
