<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5v_e750t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f5v_e750t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:folder-down-filled" {...props}></Icon>
