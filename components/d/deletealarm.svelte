<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft30jne3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ft30jne3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:deletealarm" {...props}></Icon>
