<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgpgtfkqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgpgtfkqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:business" {...props}></Icon>
