<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia3e15b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia3e15b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:note" {...props}></Icon>
