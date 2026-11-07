<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us-5s8w3u.css';
import '../../css/d/du6sep0xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us-5s8w3u"/><path clip-rule="evenodd" class="du6sep0xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copyright-outline" {...props}></Icon>
