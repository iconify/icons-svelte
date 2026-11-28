<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqr5pcb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqr5pcb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:phone-call-clock" {...props}></Icon>
