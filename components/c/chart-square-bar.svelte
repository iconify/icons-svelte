<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plt0i6b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="plt0i6b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:chart-square-bar" {...props}></Icon>
