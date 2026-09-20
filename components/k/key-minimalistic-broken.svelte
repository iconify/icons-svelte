<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bse_o5byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bse_o5byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-minimalistic-broken" {...props}></Icon>
