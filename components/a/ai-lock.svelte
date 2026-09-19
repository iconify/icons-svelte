<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/h4ip7lbpf.css';
import '../../css/s/s5vktnbeo.css';
import '../../css/u/unskt_bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="h4ip7lbpf"/><path class="s5vktnbeo"/><path class="unskt_bda"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-lock" {...props}></Icon>
