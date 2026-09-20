<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p29z2yvcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p29z2yvcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:picture" {...props}></Icon>
