<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxkl48b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fxkl48b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:edit-plant-filled" {...props}></Icon>
