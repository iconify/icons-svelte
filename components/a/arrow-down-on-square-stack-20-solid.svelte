<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d81yw8b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d81yw8b_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-on-square-stack-20-solid" {...props}></Icon>
