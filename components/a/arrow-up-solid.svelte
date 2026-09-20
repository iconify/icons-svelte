<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwmt_xb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="nwmt_xb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-up-solid" {...props}></Icon>
