<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cld0m4bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="cld0m4bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:entrance-11" {...props}></Icon>
