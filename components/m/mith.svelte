<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md6qihbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="md6qihbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:mith" {...props}></Icon>
