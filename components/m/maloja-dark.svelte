<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnmkpgmsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bnmkpgmsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:maloja-dark" {...props}></Icon>
