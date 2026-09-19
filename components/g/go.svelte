<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wydr1jbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wydr1jbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:go" {...props}></Icon>
