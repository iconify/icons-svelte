<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chq5labnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chq5labnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:alert-outline" {...props}></Icon>
