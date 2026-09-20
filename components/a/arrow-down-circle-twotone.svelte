<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/w/w6175y.css';
import '../../css/a/a-v8cn.css';
import '../../css/y/y4wbml.css';
import '../../css/o/osy4ff.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew w6175y"/><path class="a-v8cn iw1iew y4wbml"/><path class="iw1iew osy4ff y4wbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:arrow-down-circle-twotone" {...props}></Icon>
