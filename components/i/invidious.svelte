<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh20bg4_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh20bg4_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:invidious" {...props}></Icon>
