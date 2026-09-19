<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4tsa95tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g4tsa95tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-up-left-20-solid" {...props}></Icon>
