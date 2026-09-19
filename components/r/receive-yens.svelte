<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u560i_b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u560i_b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:receive-yens" {...props}></Icon>
