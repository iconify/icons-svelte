<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwh642p6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwh642p6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:coffee-x" {...props}></Icon>
