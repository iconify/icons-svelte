<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryss1iurn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryss1iurn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:f5" {...props}></Icon>
