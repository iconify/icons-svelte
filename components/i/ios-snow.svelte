<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2o7--wpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g2o7--wpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-snow" {...props}></Icon>
