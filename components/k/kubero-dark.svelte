<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivhglnbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ivhglnbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kubero-dark" {...props}></Icon>
