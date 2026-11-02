<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsq92pz-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsq92pz-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:homepod-line" {...props}></Icon>
