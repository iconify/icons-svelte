<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af8ldbcpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af8ldbcpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:e-bike-2-line" {...props}></Icon>
