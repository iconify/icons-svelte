<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sko-q4bya.css';
import '../../css/w/ww5a72t8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sko-q4bya"/><path class="ww5a72t8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:delete-time-filled" {...props}></Icon>
