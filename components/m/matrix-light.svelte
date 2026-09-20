<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocutishoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":520,"height":520};
const content = `<path class="ocutishoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:matrix-light" {...props}></Icon>
