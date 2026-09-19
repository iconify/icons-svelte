<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f69e0_7am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="f69e0_7am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:barcode" {...props}></Icon>
