<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9wwaopot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="h9wwaopot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:mercury" {...props}></Icon>
