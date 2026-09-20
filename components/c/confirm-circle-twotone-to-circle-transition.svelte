<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/s/s6fvfe.css';
import '../../css/g/gsw2zd.css';
import '../../css/f/fill-from-0_3.css';
import '../../css/s/so-to-14.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c s6fvfe"/><path class="a0m25c gsw2zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:confirm-circle-twotone-to-circle-transition" {...props}></Icon>
