<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn8ep4exf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="rn8ep4exf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hospital" {...props}></Icon>
