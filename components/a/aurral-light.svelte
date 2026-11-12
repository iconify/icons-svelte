<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mot054yqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mot054yqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aurral-light" {...props}></Icon>
