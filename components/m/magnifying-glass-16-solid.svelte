<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjvbvt49c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fjvbvt49c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:magnifying-glass-16-solid" {...props}></Icon>
