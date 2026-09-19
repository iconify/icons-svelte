<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr0e94jng.css';
import '../../css/u/uixwhfcch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cr0e94jng"/><path class="uixwhfcch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:mobile-signal" {...props}></Icon>
