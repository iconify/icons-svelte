<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwcunacxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":770,"height":1025};
const content = `<path class="fwcunacxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mapmarker" {...props}></Icon>
