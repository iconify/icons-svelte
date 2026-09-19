<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpgr4xl-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qpgr4xl-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:building-library" {...props}></Icon>
