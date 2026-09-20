<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2qekr.css';
import '../../css/i/iw1iew.css';
import '../../css/s/sqpi1o.css';
import '../../css/y/y4wbml.css';
import '../../css/n/neinwl.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-66.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2qekr iw1iew"/><path class="iw1iew sqpi1o y4wbml"/><path class="iw1iew neinwl y4wbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:alert-square-twotone" {...props}></Icon>
