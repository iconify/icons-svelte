<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh367bb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh367bb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:key-round-sharp-fill" {...props}></Icon>
