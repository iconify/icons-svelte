<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xla7vihkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xla7vihkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:folder-remove" {...props}></Icon>
