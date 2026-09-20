<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbuj5abca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbuj5abca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-top-left-broken" {...props}></Icon>
