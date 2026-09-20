<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z72rv3bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z72rv3bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:iheartradio" {...props}></Icon>
