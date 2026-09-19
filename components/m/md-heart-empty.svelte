<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0bay2vht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b0bay2vht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-heart-empty" {...props}></Icon>
