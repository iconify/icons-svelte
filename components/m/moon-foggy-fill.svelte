<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erhuk9bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erhuk9bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:moon-foggy-fill" {...props}></Icon>
