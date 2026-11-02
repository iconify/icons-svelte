<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh7zuacwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh7zuacwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drive-fill" {...props}></Icon>
