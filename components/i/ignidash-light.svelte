<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpwt8db9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rpwt8db9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ignidash-light" {...props}></Icon>
