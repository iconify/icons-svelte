<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkbrjdfog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kkbrjdfog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gosuki-light" {...props}></Icon>
