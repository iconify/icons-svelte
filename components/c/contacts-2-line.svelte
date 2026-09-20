<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx2r51bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx2r51bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:contacts-2-line" {...props}></Icon>
