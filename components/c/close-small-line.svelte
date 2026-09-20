<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gma0z2bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gma0z2bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:close-small-line" {...props}></Icon>
