<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbzvw8b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="sbzvw8b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fastdown" {...props}></Icon>
