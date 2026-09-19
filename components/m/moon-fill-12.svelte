<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/red0k8iug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="red0k8iug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:moon-fill-12" {...props}></Icon>
