<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxln1bwak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zxln1bwak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:cursor-click" {...props}></Icon>
