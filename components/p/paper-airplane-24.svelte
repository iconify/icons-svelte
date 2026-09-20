<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-h120mpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-h120mpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:paper-airplane-24" {...props}></Icon>
