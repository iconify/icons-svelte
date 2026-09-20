<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/n/n-f7_n.css';
import '../../css/x/xsxw9y.css';
import '../../css/y/y4wbml.css';
import '../../css/v/vh78wu.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-62.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew n-f7_n"/><path class="iw1iew xsxw9y y4wbml"/><path class="iw1iew vh78wu y4wbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:phone-outgoing-twotone" {...props}></Icon>
