<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c65wh9has.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c65wh9has"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-chart-bar" {...props}></Icon>
