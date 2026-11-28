<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3v2xclyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3v2xclyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cards-solid" {...props}></Icon>
