<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9c9wr01r.css';
import '../../css/r/rdsfeeb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g9c9wr01r"/><path class="rdsfeeb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:mdbook" {...props}></Icon>
