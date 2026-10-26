<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4977lbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":240,"height":96};
const content = `<path class="i4977lbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:n8n" {...props}></Icon>
