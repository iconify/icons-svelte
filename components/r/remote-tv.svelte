<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfz4o-m7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfz4o-m7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:remote-tv" {...props}></Icon>
