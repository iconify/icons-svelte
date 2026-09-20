<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5p_-5pyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b5p_-5pyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:noodle-gallery-light" {...props}></Icon>
