<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fszv21x0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fszv21x0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-rupee-16-solid" {...props}></Icon>
