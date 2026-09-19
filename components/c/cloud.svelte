<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hia-se2uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hia-se2uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:cloud" {...props}></Icon>
