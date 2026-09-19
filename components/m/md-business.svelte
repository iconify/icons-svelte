<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxzz-cb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nxzz-cb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-business" {...props}></Icon>
