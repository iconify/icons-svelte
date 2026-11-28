<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt601wb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt601wb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cart" {...props}></Icon>
