<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbw2ks26y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbw2ks26y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-down-right-broken" {...props}></Icon>
