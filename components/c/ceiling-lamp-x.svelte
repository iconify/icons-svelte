<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax4e94l0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax4e94l0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ceiling-lamp-x" {...props}></Icon>
