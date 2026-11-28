<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzgntcpqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzgntcpqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:newspaper-check" {...props}></Icon>
