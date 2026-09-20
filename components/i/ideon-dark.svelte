<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kap3k-b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kap3k-b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ideon-dark" {...props}></Icon>
