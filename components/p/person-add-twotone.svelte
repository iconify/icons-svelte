<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axscvx.css';
import '../../css/i/iw1iew.css';
import '../../css/v/v8jzga.css';
import '../../css/p/p7_ytr.css';
import '../../css/u/u2yb_n.css';
import '../../css/y/y4wbml.css';
import '../../css/o/oxmyas.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-22.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axscvx iw1iew v8jzga"/><path class="iw1iew p7_ytr v8jzga"/><path class="iw1iew u2yb_n y4wbml"/><path class="iw1iew oxmyas y4wbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:person-add-twotone" {...props}></Icon>
