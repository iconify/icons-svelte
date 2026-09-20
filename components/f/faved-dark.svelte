<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5gn_5b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c5gn_5b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:faved-dark" {...props}></Icon>
