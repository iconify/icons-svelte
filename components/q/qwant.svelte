<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tafes-bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tafes-bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:qwant" {...props}></Icon>
