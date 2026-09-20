<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgxvx1b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jgxvx1b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-add-bold" {...props}></Icon>
