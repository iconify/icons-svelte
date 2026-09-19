<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3if9bbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="z3if9bbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-crop-circle-fill-badge-xmark" {...props}></Icon>
