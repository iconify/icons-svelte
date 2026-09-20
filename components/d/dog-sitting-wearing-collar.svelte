<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km0y7xdxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="km0y7xdxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-sitting-wearing-collar" {...props}></Icon>
