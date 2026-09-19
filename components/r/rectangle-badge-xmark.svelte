<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzzv1ibam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tzzv1ibam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-badge-xmark" {...props}></Icon>
