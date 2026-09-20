<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii_k7qbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ii_k7qbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dashwise-light" {...props}></Icon>
