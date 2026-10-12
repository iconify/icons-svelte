<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi98z-bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pi98z-bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bubble-lightning-bolt-fill-20" {...props}></Icon>
