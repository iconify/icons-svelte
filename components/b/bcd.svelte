<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsun6_jdx.css';
import '../../css/i/igyvn5baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsun6_jdx"/><path class="igyvn5baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bcd" {...props}></Icon>
