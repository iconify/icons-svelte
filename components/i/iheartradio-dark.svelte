<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz5y07b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bz5y07b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:iheartradio-dark" {...props}></Icon>
