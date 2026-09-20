<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nha2ysi6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nha2ysi6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:near-protocol" {...props}></Icon>
