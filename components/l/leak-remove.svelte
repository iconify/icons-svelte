<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvk7dfb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="cvk7dfb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:leak-remove" {...props}></Icon>
