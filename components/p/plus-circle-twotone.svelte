<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4qc7h.css';
import '../../css/i/iw1iew.css';
import '../../css/u/ufkpih.css';
import '../../css/y/y4wbml.css';
import '../../css/r/r7cc1y.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4qc7h iw1iew"/><path class="iw1iew ufkpih y4wbml"/><path class="iw1iew r7cc1y y4wbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:plus-circle-twotone" {...props}></Icon>
