<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km7x9fxam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="km7x9fxam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:circle-stack-20-solid" {...props}></Icon>
