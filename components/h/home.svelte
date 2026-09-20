<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odc5s1qbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odc5s1qbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:home" {...props}></Icon>
