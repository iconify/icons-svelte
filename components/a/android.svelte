<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we22wodmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="we22wodmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:android" {...props}></Icon>
