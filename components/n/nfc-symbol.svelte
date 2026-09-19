<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqwhcbc2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fqwhcbc2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:nfc-symbol" {...props}></Icon>
