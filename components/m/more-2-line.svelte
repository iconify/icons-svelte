<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s50kqrtcf.css';
import '../../css/i/iwrg-gb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s50kqrtcf"/><path class="iwrg-gb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-2-line" {...props}></Icon>
