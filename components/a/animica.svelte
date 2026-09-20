<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh11izblh.css';
import '../../css/w/w-y4u_k5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dh11izblh"/><path class="w-y4u_k5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:animica" {...props}></Icon>
