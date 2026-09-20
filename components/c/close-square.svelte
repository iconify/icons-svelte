<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g45duuzpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g45duuzpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:close-square" {...props}></Icon>
