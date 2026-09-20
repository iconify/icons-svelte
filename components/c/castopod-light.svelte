<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldji0wbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ldji0wbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:castopod-light" {...props}></Icon>
