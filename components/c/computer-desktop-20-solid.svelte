<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp7c5ww4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tp7c5ww4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:computer-desktop-20-solid" {...props}></Icon>
