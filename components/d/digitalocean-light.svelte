<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvexj_b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cvexj_b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:digitalocean-light" {...props}></Icon>
