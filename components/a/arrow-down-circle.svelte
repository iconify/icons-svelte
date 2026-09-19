<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8cbc2bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="q8cbc2bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-down-circle" {...props}></Icon>
