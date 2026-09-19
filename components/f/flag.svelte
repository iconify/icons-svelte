<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxb4xp4od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="uxb4xp4od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:flag" {...props}></Icon>
