<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2n2h6b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2n2h6b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-search-line" {...props}></Icon>
