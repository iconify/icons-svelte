<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yslamubfc.css';
import '../../css/q/q58srweot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yslamubfc"/><path class="q58srweot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:audio-filled" {...props}></Icon>
