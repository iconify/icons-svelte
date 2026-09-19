<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cca0rsbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cca0rsbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:polaroid" {...props}></Icon>
