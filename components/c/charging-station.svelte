<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q00z02bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="q00z02bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:charging-station" {...props}></Icon>
