<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojm54hbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojm54hbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-exit" {...props}></Icon>
