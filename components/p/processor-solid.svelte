<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkkv6qbnz.css';
import '../../css/m/mg4u22kbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkkv6qbnz"/><path clip-rule="evenodd" class="mg4u22kbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:processor-solid" {...props}></Icon>
