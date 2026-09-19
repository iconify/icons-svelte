<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noy8qwcws.css';
import '../../css/v/vvvmsxc8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="noy8qwcws"/><path clip-rule="evenodd" class="vvvmsxc8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:current-location-outline" {...props}></Icon>
