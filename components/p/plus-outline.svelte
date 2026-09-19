<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl1s60bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl1s60bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:plus-outline" {...props}></Icon>
