<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0rj-esre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0rj-esre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:blood-drop-bold" {...props}></Icon>
