<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocgp66bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ocgp66bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:nest-filter" {...props}></Icon>
