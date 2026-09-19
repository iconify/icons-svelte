<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei2152blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":372,"height":512};
const content = `<path class="ei2152blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:augeas" {...props}></Icon>
