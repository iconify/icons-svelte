<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2nvqjz7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z2nvqjz7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kickstarter-dark" {...props}></Icon>
