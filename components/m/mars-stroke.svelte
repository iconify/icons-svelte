<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghv-0w7ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ghv-0w7ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mars-stroke" {...props}></Icon>
