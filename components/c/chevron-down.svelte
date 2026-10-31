<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/v/vc95bzn9u.css';
import '../../css/h/h2uz87ewu.css';
import '../../css/b/bqmpw2bfi.css';
import '../../css/e/eja-jdbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="vc95bzn9u wm-shadow"/><path class="h2uz87ewu wm-shadow"/><path class="bqmpw2bfi"/><path class="eja-jdbms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:chevron-down" {...props}></Icon>
