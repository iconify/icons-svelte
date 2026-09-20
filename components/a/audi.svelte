<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xky_hh0hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xky_hh0hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:audi" {...props}></Icon>
