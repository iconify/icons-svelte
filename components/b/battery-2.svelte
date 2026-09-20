<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewf70vbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewf70vbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-2" {...props}></Icon>
