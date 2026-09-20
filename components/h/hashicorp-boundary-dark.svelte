<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3rfa6bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q3rfa6bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-boundary-dark" {...props}></Icon>
