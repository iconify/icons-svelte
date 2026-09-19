<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyhoz-blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vyhoz-blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-alignright" {...props}></Icon>
