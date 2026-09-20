<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svjm3hclv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svjm3hclv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:circle-arrow-up" {...props}></Icon>
