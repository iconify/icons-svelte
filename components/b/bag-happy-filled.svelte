<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5z3m501d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5z3m501d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag-happy-filled" {...props}></Icon>
