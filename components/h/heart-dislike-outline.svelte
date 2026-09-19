<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otgpm3b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="otgpm3b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:heart-dislike-outline" {...props}></Icon>
