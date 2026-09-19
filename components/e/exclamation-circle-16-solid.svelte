<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb3mgp2iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hb3mgp2iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:exclamation-circle-16-solid" {...props}></Icon>
