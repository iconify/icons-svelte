<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvkuugb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rvkuugb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-note3" {...props}></Icon>
