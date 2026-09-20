<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzwzsybgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzwzsybgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-circle-fill" {...props}></Icon>
