<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ced59lb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ced59lb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:docker-compose" {...props}></Icon>
