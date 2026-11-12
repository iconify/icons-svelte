<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw8q64y9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nw8q64y9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invoiceshelf-dark" {...props}></Icon>
