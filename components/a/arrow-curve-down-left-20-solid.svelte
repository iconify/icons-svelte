<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9he1_b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d9he1_b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-down-left-20-solid" {...props}></Icon>
