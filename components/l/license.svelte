<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3g6y2-qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3g6y2-qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:license" {...props}></Icon>
