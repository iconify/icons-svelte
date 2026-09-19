<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5dmy6b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="y5dmy6b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:hand-raised-20-solid" {...props}></Icon>
