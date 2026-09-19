<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-ztj4p9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h-ztj4p9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:puppet" {...props}></Icon>
