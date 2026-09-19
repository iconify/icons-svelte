<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovlevwbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovlevwbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:coolicons" {...props}></Icon>
