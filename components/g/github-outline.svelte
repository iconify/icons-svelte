<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0kzj5b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z0kzj5b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:github-outline" {...props}></Icon>
