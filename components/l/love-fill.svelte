<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jewsv4wxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jewsv4wxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:love-fill" {...props}></Icon>
