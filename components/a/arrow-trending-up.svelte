<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1016ldf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc1016ldf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-trending-up" {...props}></Icon>
