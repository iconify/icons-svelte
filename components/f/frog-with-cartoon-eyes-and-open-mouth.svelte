<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqxrkqxhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qqxrkqxhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:frog-with-cartoon-eyes-and-open-mouth" {...props}></Icon>
