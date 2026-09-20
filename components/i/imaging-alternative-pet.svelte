<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acmwh1p4z.css';
import '../../css/e/e3v1inbws.css';
import '../../css/b/bbq7rkbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":65,"height":64};
const content = `<path class="acmwh1p4z"/><path class="e3v1inbws"/><path class="bbq7rkbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:imaging-alternative-pet" {...props}></Icon>
