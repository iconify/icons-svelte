<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvh8l4olr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvh8l4olr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-minus" {...props}></Icon>
