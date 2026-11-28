<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi-0n8byp.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/ydkjijhaq.css';
import '../../css/y/yq2tbpldz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi-0n8byp secondary"/><g class="dt0cm9dhy primary"><path class="ydkjijhaq"/><path class="yq2tbpldz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:laptop-duo" {...props}></Icon>
