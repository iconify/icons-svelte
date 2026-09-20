<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brwsvfk3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="brwsvfk3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:recycle-1-flat" {...props}></Icon>
