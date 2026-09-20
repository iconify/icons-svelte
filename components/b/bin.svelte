<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcab0ozmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wcab0ozmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bin" {...props}></Icon>
