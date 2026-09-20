<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsp4kg7um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bsp4kg7um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-word-2000-dark" {...props}></Icon>
