<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txy7xkb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="txy7xkb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-fill-badge-xmark" {...props}></Icon>
