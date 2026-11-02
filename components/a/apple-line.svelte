<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfhkvacus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfhkvacus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:apple-line" {...props}></Icon>
