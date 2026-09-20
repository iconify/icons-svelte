<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzr4-wmbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wzr4-wmbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:iheartradio-light" {...props}></Icon>
