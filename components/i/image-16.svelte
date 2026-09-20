<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl7-9-bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kl7-9-bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:image-16" {...props}></Icon>
