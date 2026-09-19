<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pijkw5bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pijkw5bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-image" {...props}></Icon>
