<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_d10yikf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_d10yikf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:butterfly-line" {...props}></Icon>
