<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slk00objf.css';
import '../../css/w/wbyo_ts-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slk00objf"/><path class="wbyo_ts-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:concert-dj-bold" {...props}></Icon>
