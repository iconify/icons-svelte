<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzxu6cbem.css';
import '../../css/y/y5x_dib_i.css';
import '../../css/b/b6edkyxdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gzxu6cbem"/><path class="y5x_dib_i"/><path class="b6edkyxdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-onedrive-dark" {...props}></Icon>
