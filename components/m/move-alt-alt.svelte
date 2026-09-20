<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik9kdpbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik9kdpbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:move-alt-alt" {...props}></Icon>
