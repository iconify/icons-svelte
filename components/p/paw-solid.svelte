<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxngbs5rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sxngbs5rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:paw-solid" {...props}></Icon>
