<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mb-rctu0w.css';
import '../../css/k/ki-z3s3do.css';
import '../../css/y/y2r41vbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mb-rctu0w"/><path class="ki-z3s3do"/><path class="y2r41vbeh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:invoice-04" {...props}></Icon>
