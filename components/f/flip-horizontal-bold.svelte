<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvxdh9bth.css';
import '../../css/h/hejbqv3cp.css';
import '../../css/p/p_2wznb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvxdh9bth"/><path class="hejbqv3cp"/><path clip-rule="evenodd" class="p_2wznb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flip-horizontal-bold" {...props}></Icon>
