<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9-e8bcrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9-e8bcrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-4-ai-line" {...props}></Icon>
