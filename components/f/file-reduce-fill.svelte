<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7l9mccln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7l9mccln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-reduce-fill" {...props}></Icon>
