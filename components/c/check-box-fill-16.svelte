<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du1gg3oja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="du1gg3oja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-box-fill-16" {...props}></Icon>
