<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w48m7-bwv.css';
import '../../css/r/r4-mswj9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w48m7-bwv"/><path class="r4-mswj9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mod" {...props}></Icon>
