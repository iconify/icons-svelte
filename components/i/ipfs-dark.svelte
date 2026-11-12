<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du0fstbco.css';
import '../../css/d/da5se5sef.css';
import '../../css/m/mle8vwbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="du0fstbco"/><path class="da5se5sef"/><path class="mle8vwbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ipfs-dark" {...props}></Icon>
