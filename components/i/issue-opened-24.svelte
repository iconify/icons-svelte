<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt0-luxxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt0-luxxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-opened-24" {...props}></Icon>
