<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3fux2b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3fux2b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-window-alt" {...props}></Icon>
