<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8vs4jsld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f8vs4jsld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:buildings-2-outline" {...props}></Icon>
