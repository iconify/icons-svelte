<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/w/w0ylnq.css';
import '../../css/i/i1bv_o.css';
import '../../css/y/y4wbml.css';
import '../../css/h/hy9wxw.css';
import '../../css/s/so-from-54.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew w0ylnq"/><path class="i1bv_o iw1iew y4wbml"/><path class="hy9wxw iw1iew y4wbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:filter-plus-filled" {...props}></Icon>
