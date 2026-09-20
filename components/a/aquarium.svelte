<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g60ojkb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g60ojkb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:aquarium" {...props}></Icon>
