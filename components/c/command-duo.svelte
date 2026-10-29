<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt-8uk4il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt-8uk4il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:command-duo" {...props}></Icon>
