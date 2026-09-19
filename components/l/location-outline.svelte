<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnzo3sbiw.css';
import '../../css/z/zfws45ina.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jnzo3sbiw"/><circle class="zfws45ina"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:location-outline" {...props}></Icon>
