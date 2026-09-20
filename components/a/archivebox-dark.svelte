<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5ob8_bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k5ob8_bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:archivebox-dark" {...props}></Icon>
