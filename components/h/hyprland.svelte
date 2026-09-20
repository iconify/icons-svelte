<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f18mgvp1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f18mgvp1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hyprland" {...props}></Icon>
