<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg9qp9bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg9qp9bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:home-minus" {...props}></Icon>
