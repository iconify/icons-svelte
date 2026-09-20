<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckh02j.css';
import '../../css/a/a0m25c.css';
import '../../css/l/lew-ud.css';
import '../../css/l/lufy5p.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckh02j"/><path class="a0m25c lew-ud"/><path class="a0m25c lufy5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:email-twotone" {...props}></Icon>
