<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s273oab-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s273oab-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-palette" {...props}></Icon>
