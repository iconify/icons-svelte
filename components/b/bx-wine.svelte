<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie19m8b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie19m8b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-wine" {...props}></Icon>
