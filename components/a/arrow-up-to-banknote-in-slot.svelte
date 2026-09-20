<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdhb7_b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kdhb7_b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-up-to-banknote-in-slot" {...props}></Icon>
