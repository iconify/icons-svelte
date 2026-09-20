<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhxajb.css';
import '../../css/o/oxmpwq.css';
import '../../css/y/yk_wkq.css';
import '../../css/t/teqz3l.css';
import '../../css/q/q5p-eg.css';
import '../../css/f/fade-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="mhxajb"/><path class="oxmpwq yk_wkq"/><path class="oxmpwq teqz3l"/><path class="oxmpwq q5p-eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:linkedin" {...props}></Icon>
