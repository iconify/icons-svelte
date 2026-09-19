<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn4nxni_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tn4nxni_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:flickr2" {...props}></Icon>
