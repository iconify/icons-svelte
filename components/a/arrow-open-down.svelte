<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/y/yt7y4i.css';
import '../../css/v/vmy1_d.css';
import '../../css/v/vmphcs.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c yt7y4i"/><path class="a0m25c vmy1_d"/><path class="a0m25c vmphcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:arrow-open-down" {...props}></Icon>
