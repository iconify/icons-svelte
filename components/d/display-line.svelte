<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en3cgfbkw.css';
import '../../css/x/xs05ygs4c.css';
import '../../css/n/nfdi2lb9a.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 en3cgfbkw"/><path class="clr-i-outline clr-i-outline-path-2 xs05ygs4c"/><path class="clr-i-outline clr-i-outline-path-3 nfdi2lb9a"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:display-line" {...props}></Icon>
