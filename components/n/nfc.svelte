<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8d68bc7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8d68bc7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:nfc" {...props}></Icon>
