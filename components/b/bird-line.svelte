<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcm2mfsay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcm2mfsay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bird-line" {...props}></Icon>
