<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adklw4bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adklw4bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-signal-5" {...props}></Icon>
