<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj437j.css';
import '../../css/i/iw1iew.css';
import '../../css/g/glst3p.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-66.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj437j iw1iew"/><path class="glst3p iw1iew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chevron-left-square-twotone" {...props}></Icon>
