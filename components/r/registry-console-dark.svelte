<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nim_7djxm.css';
import '../../css/g/gfuuvl7et.css';
import '../../css/f/fme3m9bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nim_7djxm"/><path class="gfuuvl7et"/><path class="fme3m9bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:registry-console-dark" {...props}></Icon>
