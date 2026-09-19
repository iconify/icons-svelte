<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhjen_f9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":832};
const content = `<path class="uhjen_f9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:construction" {...props}></Icon>
