<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3u21xbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3u21xbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:card-exchange-02" {...props}></Icon>
