<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni1vsp91j.css';
import '../../css/a/atbqptbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ni1vsp91j"/><path class="atbqptbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:java-interface" {...props}></Icon>
