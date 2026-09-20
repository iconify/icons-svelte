<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu46fxbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu46fxbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:automattic" {...props}></Icon>
