<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mho1zvbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mho1zvbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:amber" {...props}></Icon>
