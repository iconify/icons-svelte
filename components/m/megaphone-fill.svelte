<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6hb5pd3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x6hb5pd3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:megaphone-fill" {...props}></Icon>
