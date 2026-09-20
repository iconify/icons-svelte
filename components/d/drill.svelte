<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by8o14b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by8o14b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:drill" {...props}></Icon>
