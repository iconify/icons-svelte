<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydfvf6bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ydfvf6bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-apron2x-outline" {...props}></Icon>
