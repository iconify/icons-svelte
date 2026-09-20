<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol0neq8oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ol0neq8oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pharmacy" {...props}></Icon>
