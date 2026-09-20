<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3k28zbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l3k28zbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mend-io-dark" {...props}></Icon>
