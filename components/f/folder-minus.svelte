<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjfd3oc5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gjfd3oc5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:folder-minus" {...props}></Icon>
