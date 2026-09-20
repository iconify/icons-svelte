<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoz24cbfm.css';
import '../../css/g/g5rkwvecy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoz24cbfm"/><path class="g5rkwvecy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:desktop-monitor-smiley-bold" {...props}></Icon>
