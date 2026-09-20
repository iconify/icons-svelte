<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el1eu57nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="el1eu57nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-droplet" {...props}></Icon>
