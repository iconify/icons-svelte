<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utiac6bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="utiac6bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bow-and-arrow-fill" {...props}></Icon>
