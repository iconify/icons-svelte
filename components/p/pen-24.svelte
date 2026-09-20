<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw1xrovwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="uw1xrovwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:pen-24" {...props}></Icon>
