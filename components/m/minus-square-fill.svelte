<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8b5skbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8b5skbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:minus-square-fill" {...props}></Icon>
