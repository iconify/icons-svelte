<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdwzq7clc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdwzq7clc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folder-open-plus" {...props}></Icon>
