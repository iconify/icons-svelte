<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlyt_4bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlyt_4bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:blood-drop-filled" {...props}></Icon>
