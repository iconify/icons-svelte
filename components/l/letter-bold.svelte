<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy5q6bchh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dy5q6bchh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:letter-bold" {...props}></Icon>
