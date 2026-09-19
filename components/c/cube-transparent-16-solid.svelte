<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2f20nb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n2f20nb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cube-transparent-16-solid" {...props}></Icon>
