<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loyc48x7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="loyc48x7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:right-small-line" {...props}></Icon>
