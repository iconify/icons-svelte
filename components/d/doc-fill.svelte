<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i13lh1b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i13lh1b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:doc-fill" {...props}></Icon>
