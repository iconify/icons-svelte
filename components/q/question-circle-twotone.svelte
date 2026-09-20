<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/y/ysxzor.css';
import '../../css/d/d-j1qi.css';
import '../../css/y/y4wbml.css';
import '../../css/n/neinwl.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew ysxzor"/><path class="d-j1qi iw1iew y4wbml"/><path class="iw1iew neinwl y4wbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:question-circle-twotone" {...props}></Icon>
