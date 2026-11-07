<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmcky1b9o.css';
import '../../css/v/vyk6wnbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmcky1b9o"/><path clip-rule="evenodd" class="vyk6wnbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-close-outline" {...props}></Icon>
