<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/licz-co6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="licz-co6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-pointer" {...props}></Icon>
