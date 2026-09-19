<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3ugng94a.css';
import '../../css/j/j4wgwkb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w3ugng94a"/><path class="j4wgwkb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-graphql" {...props}></Icon>
