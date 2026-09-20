<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvlyjsbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvlyjsbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-outline" {...props}></Icon>
