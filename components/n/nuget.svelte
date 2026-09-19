<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuguap3fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nuguap3fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:nuget" {...props}></Icon>
