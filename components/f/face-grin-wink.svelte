<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg8-xqbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xg8-xqbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-grin-wink" {...props}></Icon>
