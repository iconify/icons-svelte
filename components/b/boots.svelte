<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clo7jz9rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="clo7jz9rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:boots" {...props}></Icon>
