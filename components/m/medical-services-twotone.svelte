<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/k/k2hxuz.css';
import '../../css/l/li54_l.css';
import '../../css/y/y4wbml.css';
import '../../css/p/p7uddg.css';
import '../../css/r/rrfntd.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-64.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew k2hxuz"/><path class="iw1iew li54_l y4wbml"/><path class="iw1iew p7uddg y4wbml"/><path class="iw1iew rrfntd y4wbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:medical-services-twotone" {...props}></Icon>
