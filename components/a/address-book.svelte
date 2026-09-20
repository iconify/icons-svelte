<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0ttoybfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t0ttoybfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:address-book" {...props}></Icon>
