<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dog50kb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dog50kb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:frontify" {...props}></Icon>
