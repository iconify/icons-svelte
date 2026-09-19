<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uky4vab5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="uky4vab5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:no-symbol-20-solid" {...props}></Icon>
