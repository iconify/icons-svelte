<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw_2mw1yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xw_2mw1yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:numbers" {...props}></Icon>
