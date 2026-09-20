<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j50656bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":364,"height":56};
const content = `<path class="j50656bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:character-ai" {...props}></Icon>
