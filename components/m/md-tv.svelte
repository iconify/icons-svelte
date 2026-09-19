<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt3xe-z1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gt3xe-z1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-tv" {...props}></Icon>
