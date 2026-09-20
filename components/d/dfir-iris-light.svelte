<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_2y26brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h_2y26brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dfir-iris-light" {...props}></Icon>
