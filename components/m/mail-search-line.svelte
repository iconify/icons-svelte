<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc_e77b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc_e77b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-search-line" {...props}></Icon>
