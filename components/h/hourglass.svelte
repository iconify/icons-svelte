<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bddi96b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bddi96b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hourglass" {...props}></Icon>
