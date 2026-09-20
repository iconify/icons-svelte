<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtqg49r1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtqg49r1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment" {...props}></Icon>
