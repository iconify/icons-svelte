<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv444039r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv444039r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:database-close-corner-fill-round" {...props}></Icon>
