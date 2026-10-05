<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0tjb0mmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0tjb0mmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:loader" {...props}></Icon>
