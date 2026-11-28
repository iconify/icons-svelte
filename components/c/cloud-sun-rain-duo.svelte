<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-pfn_b1g.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qtwj46vbh.css';
import '../../css/m/mbvidv7bt.css';
import '../../css/i/ifew0xbpl.css';
import '../../css/k/kh9sagb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary w-pfn_b1g"/><g class="dt0cm9dhy primary"><path class="qtwj46vbh"/><path class="mbvidv7bt"/><path class="ifew0xbpl"/><path class="kh9sagb_t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-sun-rain-duo" {...props}></Icon>
