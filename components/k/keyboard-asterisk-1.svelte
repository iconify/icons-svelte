<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw4gdnb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yw4gdnb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:keyboard-asterisk-1" {...props}></Icon>
