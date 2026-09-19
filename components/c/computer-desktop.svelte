<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kandx6b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kandx6b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:computer-desktop" {...props}></Icon>
