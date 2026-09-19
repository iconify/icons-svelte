<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqkb69uui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="eqkb69uui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-right-20-solid" {...props}></Icon>
