<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9yn35bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9yn35bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-support" {...props}></Icon>
