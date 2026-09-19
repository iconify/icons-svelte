<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzkejqbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wzkejqbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:hand-left-sharp" {...props}></Icon>
