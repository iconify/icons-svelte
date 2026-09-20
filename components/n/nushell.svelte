<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1y7ypon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc1y7ypon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nushell" {...props}></Icon>
