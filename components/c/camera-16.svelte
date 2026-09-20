<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksrkuob1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ksrkuob1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:camera-16" {...props}></Icon>
