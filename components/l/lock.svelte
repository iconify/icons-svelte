<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq0i8qkjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq0i8qkjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:lock" {...props}></Icon>
