<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv3dy9bge.css';
import '../../css/y/ye62so_7n.css';
import '../../css/i/im3g8pbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv3dy9bge"/><path clip-rule="evenodd" class="ye62so_7n"/><path class="im3g8pbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hourglass-line-bold-duotone" {...props}></Icon>
