<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cup618odg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cup618odg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:chevron-left" {...props}></Icon>
