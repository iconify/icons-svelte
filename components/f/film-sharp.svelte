<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atd8x-w7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atd8x-w7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:film-sharp" {...props}></Icon>
