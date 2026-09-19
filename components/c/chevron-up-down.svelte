<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9fw8z-ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9fw8z-ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-up-down" {...props}></Icon>
