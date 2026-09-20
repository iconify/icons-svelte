<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5vqz06yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-1.5};
const content = `<path class="e5vqz06yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:map-marker-f" {...props}></Icon>
