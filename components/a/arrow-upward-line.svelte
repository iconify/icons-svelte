<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv77v8bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv77v8bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-upward-line" {...props}></Icon>
