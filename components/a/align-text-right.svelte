<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb-7oac9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rb-7oac9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:align-text-right" {...props}></Icon>
