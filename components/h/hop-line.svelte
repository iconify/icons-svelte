<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi25h3nne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi25h3nne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hop-line" {...props}></Icon>
