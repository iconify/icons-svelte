<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-e8xsbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-e8xsbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:flask" {...props}></Icon>
