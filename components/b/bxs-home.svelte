<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn6wupbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn6wupbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-home" {...props}></Icon>
