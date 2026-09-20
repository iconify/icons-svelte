<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp9o8pb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp9o8pb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-15-line" {...props}></Icon>
