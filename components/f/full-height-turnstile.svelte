<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av1ilqbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="av1ilqbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:full-height-turnstile" {...props}></Icon>
