<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioy9bfb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ioy9bfb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calnode-dark" {...props}></Icon>
