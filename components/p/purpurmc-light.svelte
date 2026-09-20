<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p24ebsbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p24ebsbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:purpurmc-light" {...props}></Icon>
