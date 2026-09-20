<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y37et8bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y37et8bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:caret-left-right" {...props}></Icon>
