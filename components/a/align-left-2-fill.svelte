<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz1b3xbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz1b3xbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-left-2-fill" {...props}></Icon>
