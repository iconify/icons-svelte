<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x35lossty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x35lossty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nginx-dark" {...props}></Icon>
