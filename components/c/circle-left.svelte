<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mykrqg13s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mykrqg13s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:circle-left" {...props}></Icon>
