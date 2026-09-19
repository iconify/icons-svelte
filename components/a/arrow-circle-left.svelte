<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0flmbb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="v0flmbb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:arrow-circle-left" {...props}></Icon>
