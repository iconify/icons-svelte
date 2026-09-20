<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj0fh1bfy.css';
import '../../css/d/dko5xdvrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj0fh1bfy"/><path class="dko5xdvrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:bluetooth-transfer-bold" {...props}></Icon>
