<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihkf2plbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ihkf2plbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filen-light" {...props}></Icon>
