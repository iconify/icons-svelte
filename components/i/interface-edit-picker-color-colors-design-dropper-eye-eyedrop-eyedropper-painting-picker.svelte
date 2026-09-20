<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phmuk5bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="phmuk5bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-picker-color-colors-design-dropper-eye-eyedrop-eyedropper-painting-picker" {...props}></Icon>
