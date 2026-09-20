<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6pvk5uvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6pvk5uvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:move-to-bottom-24" {...props}></Icon>
