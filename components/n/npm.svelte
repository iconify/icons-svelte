<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyyle4btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="iyyle4btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:npm" {...props}></Icon>
