<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el8e7murg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="el8e7murg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:plantuml" {...props}></Icon>
