<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/h/h4mqdv.css';
import '../../css/o/o4_xet.css';
import '../../css/x/xmkx1n.css';
import '../../css/r/rw5kru.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c h4mqdv"/><path class="a0m25c o4_xet"/><path class="a0m25c xmkx1n"/><path class="a0m25c rw5kru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:hash" {...props}></Icon>
