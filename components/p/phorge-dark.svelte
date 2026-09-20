<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vscx7yblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vscx7yblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phorge-dark" {...props}></Icon>
