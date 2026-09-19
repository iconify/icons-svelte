<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa4n3fbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fa4n3fbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-warning" {...props}></Icon>
