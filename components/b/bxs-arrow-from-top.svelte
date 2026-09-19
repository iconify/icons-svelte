<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vun3xnubm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vun3xnubm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-arrow-from-top" {...props}></Icon>
