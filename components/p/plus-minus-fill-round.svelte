<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy1t6yb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy1t6yb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plus-minus-fill-round" {...props}></Icon>
