<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orbt69i5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="orbt69i5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:fist" {...props}></Icon>
