<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_8hp2bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_8hp2bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cursor-text" {...props}></Icon>
