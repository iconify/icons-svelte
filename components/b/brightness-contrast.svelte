<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd0w13brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fd0w13brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:brightness-contrast" {...props}></Icon>
