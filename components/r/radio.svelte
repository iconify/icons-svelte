<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufd3ayb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":896};
const content = `<path class="ufd3ayb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:radio" {...props}></Icon>
