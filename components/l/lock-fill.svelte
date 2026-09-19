<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enk_bkg6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="enk_bkg6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:lock-fill" {...props}></Icon>
