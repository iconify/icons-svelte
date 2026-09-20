<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgevnjv-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mgevnjv-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:paint-drop-16" {...props}></Icon>
