<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbb5ozubs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbb5ozubs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:redo-solid" {...props}></Icon>
