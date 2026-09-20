<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjnvd49sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gjnvd49sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-using-terminal-kiosk-with-yen-yuan" {...props}></Icon>
