<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5lezk8sc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5lezk8sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:paintbrush-gloss" {...props}></Icon>
