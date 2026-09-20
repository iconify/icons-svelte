<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmj-enboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="kmj-enboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:panorama" {...props}></Icon>
