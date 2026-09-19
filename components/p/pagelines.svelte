<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w451sabls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1792};
const content = `<path class="w451sabls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:pagelines" {...props}></Icon>
