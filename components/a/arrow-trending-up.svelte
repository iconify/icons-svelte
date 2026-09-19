<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayhd7rbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayhd7rbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-trending-up" {...props}></Icon>
