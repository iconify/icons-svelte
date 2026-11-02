<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cww1_ybzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cww1_ybzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:people-sleeping-in-bunkbeds-in-eaved-gabled-building-with-chimney" {...props}></Icon>
