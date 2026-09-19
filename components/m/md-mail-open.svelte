<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8jm03bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k8jm03bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-mail-open" {...props}></Icon>
