<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9kos04xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9kos04xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:database-zap-fill" {...props}></Icon>
