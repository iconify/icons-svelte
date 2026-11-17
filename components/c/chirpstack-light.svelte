<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4wh_8bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y4wh_8bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chirpstack-light" {...props}></Icon>
