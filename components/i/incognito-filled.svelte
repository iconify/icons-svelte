<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpov2tb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fpov2tb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:incognito-filled" {...props}></Icon>
