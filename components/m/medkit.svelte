<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c94btrm2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c94btrm2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:medkit" {...props}></Icon>
