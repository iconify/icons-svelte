<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbyot8xbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbyot8xbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gitextensions" {...props}></Icon>
