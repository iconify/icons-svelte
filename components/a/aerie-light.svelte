<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w14l44ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w14l44ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aerie-light" {...props}></Icon>
