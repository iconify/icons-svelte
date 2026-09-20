<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od3nh1bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="od3nh1bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:operational-dark" {...props}></Icon>
