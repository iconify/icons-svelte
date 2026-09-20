<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-7w2z-xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n-7w2z-xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:globe-solid" {...props}></Icon>
