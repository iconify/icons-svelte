<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn-h0obmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hn-h0obmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:outline-dark" {...props}></Icon>
