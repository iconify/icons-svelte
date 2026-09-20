<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdr9b6yaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdr9b6yaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:codepen" {...props}></Icon>
