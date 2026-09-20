<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl2lyq-gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl2lyq-gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-left-broken" {...props}></Icon>
