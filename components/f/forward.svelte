<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbj1nfbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbj1nfbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:forward" {...props}></Icon>
