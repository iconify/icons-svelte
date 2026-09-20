<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3-5arf6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="n3-5arf6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:hang-gliding" {...props}></Icon>
