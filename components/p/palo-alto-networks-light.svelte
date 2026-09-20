<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtvo8ubai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qtvo8ubai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:palo-alto-networks-light" {...props}></Icon>
